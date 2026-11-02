<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlxjbo3zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qlxjbo3zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:crosshair-16-solid" /></template>
