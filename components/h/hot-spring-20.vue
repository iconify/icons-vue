<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aucraj6bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aucraj6bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-spring-20" /></template>
