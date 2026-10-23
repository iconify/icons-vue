<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxf16j32g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxf16j32g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:grid-2x2-x" /></template>
