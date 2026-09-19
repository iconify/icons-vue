<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9j7jcc_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9j7jcc_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:building-alt-03-filled" /></template>
