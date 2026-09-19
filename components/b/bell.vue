<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2r-6absw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="m2r-6absw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:bell" /></template>
