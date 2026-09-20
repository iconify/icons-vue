<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir1wpry2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir1wpry2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:hash-diamond" /></template>
