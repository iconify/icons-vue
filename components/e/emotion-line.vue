<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrjemnb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrjemnb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:emotion-line" /></template>
