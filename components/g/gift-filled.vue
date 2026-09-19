<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bayoh_bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bayoh_bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:gift-filled" /></template>
