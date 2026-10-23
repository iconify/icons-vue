<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr7obeqxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr7obeqxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-chevrons-up-down" /></template>
