<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds20tl5cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds20tl5cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bath-off" /></template>
