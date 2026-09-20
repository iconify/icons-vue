<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za634pqhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za634pqhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:barricade-fill" /></template>
