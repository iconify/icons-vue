<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb4s8hb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="cb4s8hb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hiking" /></template>
