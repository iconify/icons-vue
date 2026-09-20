<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo1-5mpqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":62,"height":24};
const content = `<path clip-rule="evenodd" class="qo1-5mpqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:arc-light" /></template>
