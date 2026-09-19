<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxbq9ib_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zxbq9ib_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-analytics" /></template>
