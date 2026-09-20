<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc6_jgsyo.css';
import '../../css/t/tc5lk5bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xc6_jgsyo"/><path class="tc5lk5bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bed-single-solid" /></template>
