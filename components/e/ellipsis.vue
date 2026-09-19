<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix4609bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix4609bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:ellipsis" /></template>
