<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2g8xf7jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2g8xf7jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:improvmx" /></template>
