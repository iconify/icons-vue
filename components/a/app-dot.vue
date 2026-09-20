<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6qhu6bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6qhu6bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-dot" /></template>
