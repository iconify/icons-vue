<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itgi-tjpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="itgi-tjpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:hotjar" /></template>
