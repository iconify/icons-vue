<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og2ty2bhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og2ty2bhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:infinite-filled" /></template>
