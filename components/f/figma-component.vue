<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaetcy9pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vaetcy9pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:figma-component" /></template>
