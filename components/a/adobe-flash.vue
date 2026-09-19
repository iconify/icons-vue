<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af_nybbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="af_nybbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-flash" /></template>
