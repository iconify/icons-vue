<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqukh3bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqukh3bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:attachment" /></template>
