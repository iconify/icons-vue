<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn46jyyfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn46jyyfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bell-x-solid" /></template>
