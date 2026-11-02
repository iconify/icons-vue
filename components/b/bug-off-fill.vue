<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvze28blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvze28blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bug-off-fill" /></template>
