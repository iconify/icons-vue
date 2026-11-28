<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yznny6i3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yznny6i3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:brain" /></template>
