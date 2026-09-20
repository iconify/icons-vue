<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t63efkb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t63efkb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eyedropper-remove" /></template>
