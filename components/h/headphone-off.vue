<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sleixublu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sleixublu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:headphone-off" /></template>
