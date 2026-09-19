<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq6g47b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zq6g47b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:list-rich" /></template>
