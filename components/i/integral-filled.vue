<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf6dqzroz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zf6dqzroz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:integral-filled" /></template>
