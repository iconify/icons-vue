<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbrp5rbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hbrp5rbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-sun-rain" /></template>
