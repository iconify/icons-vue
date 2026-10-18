<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcbfky4-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcbfky4-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:battery-full" /></template>
