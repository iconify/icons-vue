<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngppwkb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngppwkb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-audio-plus" /></template>
