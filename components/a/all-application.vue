<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9q_l8kgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w9q_l8kgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:all-application" /></template>
