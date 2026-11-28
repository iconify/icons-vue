<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpk0tl1ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpk0tl1ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:layout-plus" /></template>
