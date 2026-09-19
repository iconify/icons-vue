<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n35slstzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n35slstzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:bulb-filled" /></template>
