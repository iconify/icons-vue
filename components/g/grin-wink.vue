<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc66k6u8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cc66k6u8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grin-wink" /></template>
