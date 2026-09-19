<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkcnz7bbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="kkcnz7bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-uturn-left" /></template>
