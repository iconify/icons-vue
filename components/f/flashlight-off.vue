<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcwb-tbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcwb-tbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:flashlight-off" /></template>
