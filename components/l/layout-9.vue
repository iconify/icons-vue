<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps15tebrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="ps15tebrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:layout-9" /></template>
