<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd3eww85q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bd3eww85q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:health-24px" /></template>
