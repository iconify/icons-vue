<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnr7hi9rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnr7hi9rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:flame" /></template>
