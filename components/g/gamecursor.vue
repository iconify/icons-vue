<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc51-mbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nc51-mbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:gamecursor" /></template>
