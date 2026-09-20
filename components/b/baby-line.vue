<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy-g8lbjc.css';
import '../../css/c/c_jcusmko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy-g8lbjc"/><path class="c_jcusmko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:baby-line" /></template>
