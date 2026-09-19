<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr_9r198d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nr_9r198d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:leaf" /></template>
