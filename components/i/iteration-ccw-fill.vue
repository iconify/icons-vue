<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihk2tf_ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihk2tf_ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:iteration-ccw-fill" /></template>
