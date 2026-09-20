<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6_fz7-2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6_fz7-2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fire-solid" /></template>
