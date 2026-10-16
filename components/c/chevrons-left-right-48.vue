<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq-tdwb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qq-tdwb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-left-right-48" /></template>
