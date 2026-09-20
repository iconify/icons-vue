<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rog9c546b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rog9c546b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:digg" /></template>
