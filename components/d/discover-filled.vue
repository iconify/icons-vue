<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2y87ub0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2y87ub0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:discover-filled" /></template>
