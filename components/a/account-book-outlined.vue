<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqov4sbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kqov4sbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:account-book-outlined" /></template>
