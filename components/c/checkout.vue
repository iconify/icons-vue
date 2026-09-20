<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkg-e7bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vkg-e7bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:checkout" /></template>
