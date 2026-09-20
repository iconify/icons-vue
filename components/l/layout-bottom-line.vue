<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w367kk4-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w367kk4-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-bottom-line" /></template>
