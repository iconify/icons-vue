<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gztvgb2-v.css';
import '../../css/x/xqf3i9bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gztvgb2-v"/><path clip-rule="evenodd" class="xqf3i9bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:eps-solid" /></template>
