<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isok_lbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="isok_lbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:circle-close-filled" /></template>
