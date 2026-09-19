<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iby7qcc7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iby7qcc7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:exclamation-outlined" /></template>
