<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjs2h1e2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjs2h1e2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:children-must-be-supervised" /></template>
