<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhs0kabae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qhs0kabae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:difference-set" /></template>
