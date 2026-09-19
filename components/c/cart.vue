<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxr6ncb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yxr6ncb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:cart" /></template>
