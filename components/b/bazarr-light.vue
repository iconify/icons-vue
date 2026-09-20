<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7f_wj1ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c7f_wj1ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bazarr-light" /></template>
