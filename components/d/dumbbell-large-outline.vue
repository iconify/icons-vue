<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8539_gwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q8539_gwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbell-large-outline" /></template>
