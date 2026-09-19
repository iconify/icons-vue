<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5pa9y0qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="g5pa9y0qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-up-circle" /></template>
