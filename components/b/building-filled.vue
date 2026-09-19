<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_bqfmbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_bqfmbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:building-filled" /></template>
