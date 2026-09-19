<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryi47hrkh.css';
import '../../css/h/h41dyrd2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryi47hrkh"/><path class="h41dyrd2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bookmarks" /></template>
