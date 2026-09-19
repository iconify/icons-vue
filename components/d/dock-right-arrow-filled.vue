<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xczuevcqe.css';
import '../../css/p/pq0jslbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xczuevcqe"/><path class="pq0jslbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-right-arrow-filled" /></template>
