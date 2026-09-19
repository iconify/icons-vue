<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1afvzb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":850};
const content = `<path class="j1afvzb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:brightness" /></template>
