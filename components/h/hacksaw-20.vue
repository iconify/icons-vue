<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7xjbxbqp.css';
import '../../css/m/mi71ysxct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i7xjbxbqp"/><path class="mi71ysxct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hacksaw-20" /></template>
