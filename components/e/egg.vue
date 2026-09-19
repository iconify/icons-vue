<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvwb1mbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvwb1mbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:egg" /></template>
