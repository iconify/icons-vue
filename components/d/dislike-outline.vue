<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myf3l1ujr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="myf3l1ujr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dislike-outline" /></template>
