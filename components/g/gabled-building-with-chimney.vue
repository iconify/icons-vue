<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgwh5lbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bgwh5lbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gabled-building-with-chimney" /></template>
