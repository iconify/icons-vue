<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkeyf6b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="bkeyf6b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bars" /></template>
