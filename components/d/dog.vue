<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8se2sqaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n8se2sqaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dog" /></template>
