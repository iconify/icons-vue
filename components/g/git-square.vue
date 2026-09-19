<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmho76qch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="gmho76qch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:git-square" /></template>
