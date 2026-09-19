<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck8_mw97s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ck8_mw97s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:house-chimney-medical" /></template>
