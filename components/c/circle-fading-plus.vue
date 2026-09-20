<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl2vbwbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl2vbwbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:circle-fading-plus" /></template>
