<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amd5b9b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="amd5b9b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:code-climate" /></template>
