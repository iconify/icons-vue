<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0_6e3iib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="o0_6e3iib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:cone" /></template>
