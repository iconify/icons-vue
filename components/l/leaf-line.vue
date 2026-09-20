<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj9p6zbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj9p6zbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:leaf-line" /></template>
