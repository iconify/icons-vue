<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffhh3qb8v.css';
import '../../css/s/sfre7fbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffhh3qb8v"/><path class="sfre7fbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:box" /></template>
