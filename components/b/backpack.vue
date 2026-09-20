<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jglel6bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jglel6bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:backpack" /></template>
