<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4qvaultt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="s4qvaultt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bulb-2" /></template>
