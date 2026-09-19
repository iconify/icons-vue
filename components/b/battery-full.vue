<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1ao6026r.css';
import '../../css/c/cxr0b5brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1ao6026r"/><rect class="cxr0b5brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:battery-full" /></template>
