<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa3-w-bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa3-w-bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crop-16-9" /></template>
