<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irbdrs3va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="irbdrs3va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:copyright-outline" /></template>
