<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd-rz_mmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="rd-rz_mmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hourglass-half" /></template>
