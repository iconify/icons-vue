<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8wyaabxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="d8wyaabxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrows-turn-right" /></template>
