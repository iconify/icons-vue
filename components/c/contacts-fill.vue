<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0zxo92_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u0zxo92_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:contacts-fill" /></template>
