<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn-zulx8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn-zulx8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:link" /></template>
