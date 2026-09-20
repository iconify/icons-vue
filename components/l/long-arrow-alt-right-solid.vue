<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdn6n-b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bdn6n-b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:long-arrow-alt-right-solid" /></template>
