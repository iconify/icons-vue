<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hernl_b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="hernl_b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:celsius" /></template>
