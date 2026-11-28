<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0aa-qdix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0aa-qdix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:list-checks" /></template>
