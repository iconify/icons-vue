<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww4fyqbuj.css';
import '../../css/d/da0t0goah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ww4fyqbuj"/><path class="da0t0goah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:face-neutral" /></template>
