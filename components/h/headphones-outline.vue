<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd5lbcb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd5lbcb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:headphones-outline" /></template>
