<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaa4zmyug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eaa4zmyug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:book-add-filled" /></template>
