<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4paecbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4paecbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:alarm-bell-ring-bold" /></template>
