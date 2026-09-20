<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp081n6cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp081n6cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder4" /></template>
