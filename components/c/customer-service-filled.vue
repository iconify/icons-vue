<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxwzybcxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jxwzybcxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:customer-service-filled" /></template>
