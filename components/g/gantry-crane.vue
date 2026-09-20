<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmgn0uboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmgn0uboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gantry-crane" /></template>
