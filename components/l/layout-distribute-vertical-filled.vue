<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2d6209ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2d6209ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-distribute-vertical-filled" /></template>
