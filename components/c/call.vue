<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdj4t8jqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdj4t8jqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call" /></template>
