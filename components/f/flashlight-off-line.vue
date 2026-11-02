<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se9_lvtty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se9_lvtty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flashlight-off-line" /></template>
