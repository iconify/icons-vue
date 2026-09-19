<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu_yqmbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":432};
const content = `<path class="zu_yqmbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-paint" /></template>
