<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk6elqb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk6elqb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:binary-tree" /></template>
