<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc3e-fbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pc3e-fbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:clipboard-solid" /></template>
