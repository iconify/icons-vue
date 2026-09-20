<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj4xopbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj4xopbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kluster" /></template>
