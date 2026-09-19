<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noday15di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="noday15di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:filter-list-circle-solid" /></template>
