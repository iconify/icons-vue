<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o86-0b4qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="o86-0b4qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:discover" /></template>
