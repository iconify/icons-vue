<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c19up3bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c19up3bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:inventory-filled" /></template>
