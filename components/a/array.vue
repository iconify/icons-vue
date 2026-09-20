<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm1-0cdzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm1-0cdzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:array" /></template>
