<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chkcovbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="chkcovbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:lightbulb" /></template>
