<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3bs-cb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v3bs-cb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:forumbee" /></template>
