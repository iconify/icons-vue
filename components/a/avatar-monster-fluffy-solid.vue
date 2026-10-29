<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6x5pmbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6x5pmbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-monster-fluffy-solid" /></template>
