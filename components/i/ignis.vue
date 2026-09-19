<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf5tybb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kf5tybb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ignis" /></template>
