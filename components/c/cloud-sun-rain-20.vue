<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvnnf13zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hvnnf13zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-sun-rain-20" /></template>
