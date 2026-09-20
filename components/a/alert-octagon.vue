<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkr_chbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="hkr_chbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alert-octagon" /></template>
