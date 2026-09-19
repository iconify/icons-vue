<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f33c5bbfy.css';
import '../../css/y/yv_brepse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f33c5bbfy"/><path class="yv_brepse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:down-circle-outlined" /></template>
