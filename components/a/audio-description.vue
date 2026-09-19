<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba8_jhblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1280};
const content = `<path class="ba8_jhblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:audio-description" /></template>
