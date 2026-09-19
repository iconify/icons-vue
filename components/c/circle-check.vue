<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dip7kslof.css';
import '../../css/t/t55-6mljh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dip7kslof"/><path class="t55-6mljh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:circle-check" /></template>
