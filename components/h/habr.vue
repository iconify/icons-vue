<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn3t6_bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn3t6_bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:habr" /></template>
