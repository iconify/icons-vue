<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilnlo62ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ilnlo62ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-bin" /></template>
