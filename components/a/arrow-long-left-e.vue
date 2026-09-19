<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh4xrsbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bh4xrsbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-left-e" /></template>
