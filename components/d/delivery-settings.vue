<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el98wicub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="el98wicub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:delivery-settings" /></template>
