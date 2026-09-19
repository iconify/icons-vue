<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va3pt_bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="va3pt_bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cloud" /></template>
