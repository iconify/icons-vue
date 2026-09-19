<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_zm2yjss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="i_zm2yjss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:location-marker" /></template>
