<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c51wj6ovw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="c51wj6ovw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:flood" /></template>
