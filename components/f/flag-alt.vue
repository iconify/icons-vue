<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aku1-wbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="aku1-wbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:flag-alt" /></template>
