<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywd6cmbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ywd6cmbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:grip-lines" /></template>
