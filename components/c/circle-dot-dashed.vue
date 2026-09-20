<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv09wxrvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv09wxrvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-dot-dashed" /></template>
