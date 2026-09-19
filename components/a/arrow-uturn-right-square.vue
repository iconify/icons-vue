<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbkbw5byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bbkbw5byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-uturn-right-square" /></template>
