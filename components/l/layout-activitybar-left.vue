<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz59rmb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zz59rmb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-activitybar-left" /></template>
