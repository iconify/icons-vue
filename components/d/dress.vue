<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6sdug4jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="y6sdug4jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:dress" /></template>
