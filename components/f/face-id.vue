<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy63rh4wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy63rh4wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:face-id" /></template>
