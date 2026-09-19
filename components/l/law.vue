<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn3q1jd5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn3q1jd5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:law" /></template>
