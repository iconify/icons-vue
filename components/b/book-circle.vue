<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzooad_xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tzooad_xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:book-circle" /></template>
