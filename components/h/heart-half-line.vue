<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df9dcob8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df9dcob8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heart-half-line" /></template>
