<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd_wcpgiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gd_wcpgiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:dice" /></template>
