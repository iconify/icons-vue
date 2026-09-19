<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja-b65-6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ja-b65-6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:book" /></template>
