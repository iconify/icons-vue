<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgw1jclaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kgw1jclaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:glasses-solid" /></template>
