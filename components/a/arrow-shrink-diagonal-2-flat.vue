<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v--621bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v--621bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-shrink-diagonal-2-flat" /></template>
