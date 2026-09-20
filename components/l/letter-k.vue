<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3v-bh0qy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3v-bh0qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-k" /></template>
