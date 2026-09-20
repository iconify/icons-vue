<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3nu1cc-n.css';
import '../../css/m/m7_384bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960,"top":-960};
const content = `<path class="s3nu1cc-n"/><path class="m7_384bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:actionscript" /></template>
