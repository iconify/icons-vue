<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko59n4btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ko59n4btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:forward-square-f" /></template>
