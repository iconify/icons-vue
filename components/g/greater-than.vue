<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9xe9obue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="h9xe9obue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:greater-than" /></template>
