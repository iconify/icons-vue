<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj2lqzbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj2lqzbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flask-2-fill" /></template>
