<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yru80ibvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yru80ibvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:battery-plus" /></template>
