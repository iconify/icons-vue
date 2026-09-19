<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6syj6bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="p6syj6bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:angle-up" /></template>
