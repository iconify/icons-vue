<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8ts7hg1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b8ts7hg1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:bold-outline" /></template>
