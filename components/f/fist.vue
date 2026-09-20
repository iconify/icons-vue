<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cidl79b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cidl79b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:fist" /></template>
