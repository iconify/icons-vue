<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aragomboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aragomboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:left-to-right-list-dash" /></template>
