<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azn5tbz7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azn5tbz7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:command" /></template>
