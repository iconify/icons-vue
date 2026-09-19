<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lic9wnnrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lic9wnnrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:file-folder" /></template>
