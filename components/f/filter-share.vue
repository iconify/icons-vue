<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me9yveb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me9yveb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-share" /></template>
