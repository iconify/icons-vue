<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnwj9rb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnwj9rb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:brain-01" /></template>
