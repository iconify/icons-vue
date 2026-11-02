<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwdetfb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lwdetfb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:gender-trans-16-solid" /></template>
