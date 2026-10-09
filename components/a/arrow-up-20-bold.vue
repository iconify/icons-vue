<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjx8q2jsf.css';
import '../../css/e/ez3axdbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jjx8q2jsf"/><path class="ez3axdbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-20-bold" /></template>
