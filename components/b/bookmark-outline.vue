<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uly7bsagg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="uly7bsagg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:bookmark-outline" /></template>
