<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de6mm3bss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="de6mm3bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-down-z-a" /></template>
