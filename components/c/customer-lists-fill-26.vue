<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs8xnjyqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="fs8xnjyqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:customer-lists-fill-26" /></template>
