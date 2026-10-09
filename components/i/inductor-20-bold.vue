<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-i2hghui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l-i2hghui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:inductor-20-bold" /></template>
