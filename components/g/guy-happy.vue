<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn1zf-bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jn1zf-bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:guy-happy" /></template>
