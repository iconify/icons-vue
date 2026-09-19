<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u35j8-mcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u35j8-mcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:gmt" /></template>
