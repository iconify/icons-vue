<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pecnj0bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pecnj0bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chart-pie-fill" /></template>
