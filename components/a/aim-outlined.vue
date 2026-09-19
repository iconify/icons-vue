<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trohwccmt.css';
import '../../css/e/eq354xb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="trohwccmt"/><path class="eq354xb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:aim-outlined" /></template>
