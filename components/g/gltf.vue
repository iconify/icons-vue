<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy6a_fh8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dy6a_fh8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gltf" /></template>
