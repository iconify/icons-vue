<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp5pjiolx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="xp5pjiolx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:heartbeat" /></template>
