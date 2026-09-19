<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8l94bcrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f8l94bcrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:four-leaves" /></template>
