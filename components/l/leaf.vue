<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-_303-2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-_303-2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:leaf" /></template>
