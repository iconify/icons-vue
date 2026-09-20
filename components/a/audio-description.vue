<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxo88edev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cxo88edev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:audio-description" /></template>
