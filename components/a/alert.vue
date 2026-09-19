<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m44z8bb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m44z8bb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:alert" /></template>
