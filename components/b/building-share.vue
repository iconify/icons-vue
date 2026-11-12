<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5upftd6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5upftd6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-share" /></template>
