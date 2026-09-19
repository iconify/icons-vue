<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysfw4hkul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ysfw4hkul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:group" /></template>
