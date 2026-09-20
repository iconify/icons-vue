<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f--jrem6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f--jrem6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:color-picker-2-bold" /></template>
