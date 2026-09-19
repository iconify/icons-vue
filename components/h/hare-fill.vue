<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eed4xfb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="eed4xfb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:hare-fill" /></template>
