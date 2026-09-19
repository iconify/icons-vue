<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au_he4sgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="au_he4sgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-left-dots-fill" /></template>
