<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kah53cyve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kah53cyve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:file-audio" /></template>
