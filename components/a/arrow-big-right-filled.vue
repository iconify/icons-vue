<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y73888bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y73888bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-big-right-filled" /></template>
