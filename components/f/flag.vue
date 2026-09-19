<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke23d28rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ke23d28rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:flag" /></template>
