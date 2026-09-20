<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weqf-9bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="weqf-9bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-merge-left" /></template>
