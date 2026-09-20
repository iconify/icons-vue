<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn2gqpb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn2gqpb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:list-ordered-2" /></template>
