<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxn65k2kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxn65k2kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:feather-filled" /></template>
