<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi6s0tcxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hi6s0tcxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dumbbell" /></template>
