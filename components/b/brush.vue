<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwmun5b1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dwmun5b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:brush" /></template>
