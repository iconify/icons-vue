<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da7zqbe4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="da7zqbe4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:js" /></template>
