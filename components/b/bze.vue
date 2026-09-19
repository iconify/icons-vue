<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlvjc1tia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hlvjc1tia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bze" /></template>
