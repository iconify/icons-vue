<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s19-dyb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s19-dyb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-arrow-dropright" /></template>
