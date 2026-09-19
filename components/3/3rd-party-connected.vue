<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5it-si_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g5it-si_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:3rd-party-connected" /></template>
