<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n19ce9b0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n19ce9b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:deepmind" /></template>
