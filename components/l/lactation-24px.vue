<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j16jsh-6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j16jsh-6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:lactation-24px" /></template>
