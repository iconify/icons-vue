<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwcaxdhsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dwcaxdhsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cube" /></template>
