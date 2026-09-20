<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq-e0mx3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq-e0mx3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:brightness-low-solid" /></template>
