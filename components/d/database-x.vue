<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r190aubtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r190aubtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:database-x" /></template>
