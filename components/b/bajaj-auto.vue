<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lktgmqyfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":120};
const content = `<path class="lktgmqyfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bajaj-auto" /></template>
