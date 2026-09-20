<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0cenz3yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h0cenz3yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:facebook-square" /></template>
