<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy5lmc-ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy5lmc-ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:filter-outline" /></template>
