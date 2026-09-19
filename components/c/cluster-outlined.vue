<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar355_tpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ar355_tpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:cluster-outlined" /></template>
