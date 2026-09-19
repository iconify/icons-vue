<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojjz05b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":800};
const content = `<path class="ojjz05b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:dialog" /></template>
