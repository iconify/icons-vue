<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyggh3xhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dyggh3xhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:circle-up" /></template>
