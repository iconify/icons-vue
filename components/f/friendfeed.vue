<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljky9acbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ljky9acbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:friendfeed" /></template>
