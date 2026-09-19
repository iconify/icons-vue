<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee218fbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ee218fbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:check-outline" /></template>
