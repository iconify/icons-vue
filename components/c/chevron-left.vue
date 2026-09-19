<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir1z2yyne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="ir1z2yyne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chevron-left" /></template>
