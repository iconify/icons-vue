<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbumxlbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lbumxlbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down-circle-20-solid" /></template>
