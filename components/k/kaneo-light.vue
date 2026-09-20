<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1io2pbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k1io2pbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kaneo-light" /></template>
