<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfsz-uvig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1280};
const content = `<path class="sfsz-uvig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bicycle" /></template>
