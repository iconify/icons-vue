<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtsq4kr0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtsq4kr0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arrow-left" /></template>
