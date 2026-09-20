<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c86s1l3_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c86s1l3_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-down-left" /></template>
