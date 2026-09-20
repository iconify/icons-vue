<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvpr1296f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvpr1296f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:add-rhombus" /></template>
