<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_kkayb9j.css';
import '../../css/i/iiryr56qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c_kkayb9j"/><path class="iiryr56qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:earth-southeast-asia-filled" /></template>
