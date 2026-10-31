<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaig3pn7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaig3pn7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-plus-round" /></template>
