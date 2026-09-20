<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-51n6uqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-51n6uqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:align-left" /></template>
