<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejdx2fbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ejdx2fbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cloud-moon-rain-solid" /></template>
