<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvbo4bbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvbo4bbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cake-solid" /></template>
