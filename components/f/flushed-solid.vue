<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw7aqqbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zw7aqqbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:flushed-solid" /></template>
