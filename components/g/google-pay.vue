<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca0v-9y6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ca0v-9y6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:google-pay" /></template>
