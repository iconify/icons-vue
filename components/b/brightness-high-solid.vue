<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o56yifc7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o56yifc7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brightness-high-solid" /></template>
