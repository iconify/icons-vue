<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtfvev2af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jtfvev2af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:location" /></template>
