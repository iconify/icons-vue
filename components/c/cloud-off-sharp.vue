<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3u9yv-3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3u9yv-3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-off-sharp" /></template>
