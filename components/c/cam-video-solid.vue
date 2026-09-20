<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_det40ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_det40ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cam-video-solid" /></template>
