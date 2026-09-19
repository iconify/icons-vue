<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7ddr5vqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="g7ddr5vqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-sun-with-rays-small-filled" /></template>
