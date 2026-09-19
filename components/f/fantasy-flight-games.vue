<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahk1xk91p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ahk1xk91p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:fantasy-flight-games" /></template>
