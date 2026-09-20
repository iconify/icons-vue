<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8v8xo1sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i8v8xo1sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:address-book" /></template>
