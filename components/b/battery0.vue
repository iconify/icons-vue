<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms81w8yjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ms81w8yjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:battery0" /></template>
