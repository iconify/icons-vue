<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny-96bjvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ny-96bjvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:checklist-16-solid" /></template>
