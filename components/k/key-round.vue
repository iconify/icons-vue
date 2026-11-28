<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go_1ac-5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go_1ac-5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:key-round" /></template>
