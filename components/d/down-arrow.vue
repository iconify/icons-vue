<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el-86ccvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el-86ccvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:down-arrow" /></template>
