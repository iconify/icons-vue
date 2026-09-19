<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nygw9lbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="nygw9lbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:key" /></template>
