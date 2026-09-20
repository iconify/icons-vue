<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgzl3pbub.css';
import '../../css/y/yixh8cciz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dgzl3pbub"/><path class="yixh8cciz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:coffee-shop" /></template>
