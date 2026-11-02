<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb0rxhbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gb0rxhbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:corners-pointing-in-20-solid" /></template>
