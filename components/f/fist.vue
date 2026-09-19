<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orbt69i5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="orbt69i5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:fist" /></template>
