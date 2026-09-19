<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho08mcb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ho08mcb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:list" /></template>
