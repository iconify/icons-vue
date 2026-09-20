<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s74x4zxov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s74x4zxov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:air-freshener-solid" /></template>
