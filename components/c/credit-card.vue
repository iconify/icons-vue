<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijc_7ccrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ijc_7ccrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:credit-card" /></template>
