<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3n3ghbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="r3n3ghbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:audio-spectrum" /></template>
