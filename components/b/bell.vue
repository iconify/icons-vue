<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe3wgdbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qe3wgdbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:bell" /></template>
