<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5r00xbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l5r00xbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-video-fill" /></template>
