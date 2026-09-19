<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfzc_4bcf.css';
import '../../css/x/x645877qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfzc_4bcf"/><path class="x645877qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:beer-mug-full" /></template>
