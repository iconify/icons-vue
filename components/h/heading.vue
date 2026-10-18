<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7rfvudmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7rfvudmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading" /></template>
