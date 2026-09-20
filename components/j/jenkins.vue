<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3je_kq8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u3je_kq8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:jenkins" /></template>
