<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex1k3z4qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex1k3z4qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:coffee-alt" /></template>
