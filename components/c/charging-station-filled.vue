<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cajxjqbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cajxjqbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:charging-station-filled" /></template>
