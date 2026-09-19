<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebl_hvbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ebl_hvbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-square-quote-fill" /></template>
