<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um9ch0b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="um9ch0b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:bolt" /></template>
