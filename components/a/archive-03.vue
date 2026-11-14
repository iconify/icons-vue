<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2e31-bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2e31-bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:archive-03" /></template>
