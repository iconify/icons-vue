<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv1vq517n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv1vq517n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:cloud-upload" /></template>
