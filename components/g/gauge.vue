<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6fali1_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="g6fali1_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:gauge" /></template>
