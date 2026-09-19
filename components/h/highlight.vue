<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywzk8rb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywzk8rb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:highlight" /></template>
