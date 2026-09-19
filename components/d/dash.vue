<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow10mebrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ow10mebrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:dash" /></template>
