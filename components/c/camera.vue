<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swwrsubca.css';
import '../../css/g/g0ga_t5io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="swwrsubca"/><path class="g0ga_t5io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:camera" /></template>
