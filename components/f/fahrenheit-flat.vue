<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh3-93bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oh3-93bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:fahrenheit-flat" /></template>
