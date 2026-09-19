<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uasa_bcbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uasa_bcbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:airplane-fill" /></template>
