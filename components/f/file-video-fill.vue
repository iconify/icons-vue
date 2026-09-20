<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhm_dub_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhm_dub_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-video-fill" /></template>
