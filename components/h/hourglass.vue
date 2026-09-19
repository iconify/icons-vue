<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bddi96b0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bddi96b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hourglass" /></template>
