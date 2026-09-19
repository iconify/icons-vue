<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9y_fntnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="b9y_fntnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:amazon" /></template>
