<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/munw0bbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="munw0bbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bay" /></template>
