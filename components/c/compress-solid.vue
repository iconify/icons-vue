<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c62wa0bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c62wa0bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:compress-solid" /></template>
