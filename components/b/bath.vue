<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agz0m6b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="agz0m6b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bath" /></template>
