<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqx0c2-nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqx0c2-nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:delete-bin-7-fill" /></template>
