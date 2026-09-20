<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9d87e5ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v9d87e5ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:angle-double-left-solid" /></template>
