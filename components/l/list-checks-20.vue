<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk1v-uboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yk1v-uboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-checks-20" /></template>
