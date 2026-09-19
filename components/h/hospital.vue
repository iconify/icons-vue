<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp03xxb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="wp03xxb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:hospital" /></template>
