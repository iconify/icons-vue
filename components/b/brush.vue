<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi4mg4ubu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="zi4mg4ubu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:brush" /></template>
