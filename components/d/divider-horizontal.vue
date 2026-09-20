<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j28c1wjbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j28c1wjbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:divider-horizontal" /></template>
