<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s95tdh2ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s95tdh2ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-right-end-on-rectangle-solid" /></template>
