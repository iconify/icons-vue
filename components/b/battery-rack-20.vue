<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mocog6boj.css';
import '../../css/h/ho9y8vbhq.css';
import '../../css/v/vi_8ex1lt.css';
import '../../css/a/alhk8c02y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mocog6boj"/><path class="ho9y8vbhq"/><path class="vi_8ex1lt"/><path class="alhk8c02y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-rack-20" /></template>
