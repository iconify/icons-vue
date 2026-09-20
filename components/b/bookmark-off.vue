<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szb74yk6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szb74yk6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-off" /></template>
