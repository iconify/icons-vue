<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jav4t0bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jav4t0bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bed-double" /></template>
