<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw9y5ibzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fw9y5ibzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:lego" /></template>
