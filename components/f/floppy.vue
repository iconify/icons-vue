<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5o_g32uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="h5o_g32uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:floppy" /></template>
