<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe8kw5b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe8kw5b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-offset-bottom" /></template>
