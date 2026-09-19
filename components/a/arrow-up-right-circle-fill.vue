<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lau9ehbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lau9ehbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-right-circle-fill" /></template>
