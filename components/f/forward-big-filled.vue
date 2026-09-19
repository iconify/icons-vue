<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkjo60blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkjo60blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:forward-big-filled" /></template>
