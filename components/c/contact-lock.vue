<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmswr3_ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pmswr3_ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:contact-lock" /></template>
