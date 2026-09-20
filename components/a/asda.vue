<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op-b1jbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op-b1jbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:asda" /></template>
