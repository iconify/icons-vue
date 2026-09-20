<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp694xb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp694xb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:fiscal-host-24" /></template>
