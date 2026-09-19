<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvuvnwh7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kvuvnwh7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlehammer" /></template>
