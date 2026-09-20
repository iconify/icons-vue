<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgq-79blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgq-79blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:cat-big" /></template>
