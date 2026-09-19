<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st78s92ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st78s92ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cart" /></template>
