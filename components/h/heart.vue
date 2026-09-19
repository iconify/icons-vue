<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7gm_zboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q7gm_zboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:heart" /></template>
