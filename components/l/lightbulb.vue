<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya7o16w0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya7o16w0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:lightbulb" /></template>
