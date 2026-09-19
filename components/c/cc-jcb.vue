<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja3dp1woh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1536};
const content = `<path class="ja3dp1woh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cc-jcb" /></template>
