<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juppfpb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="juppfpb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:facebook-f" /></template>
