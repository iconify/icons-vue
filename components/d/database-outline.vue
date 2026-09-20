<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s83cy2i3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s83cy2i3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:database-outline" /></template>
