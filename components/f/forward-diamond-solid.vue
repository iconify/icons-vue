<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6bfirbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6bfirbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:forward-diamond-solid" /></template>
