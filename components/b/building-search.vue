<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wax_9p6id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wax_9p6id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-search" /></template>
