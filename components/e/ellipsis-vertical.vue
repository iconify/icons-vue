<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4mqbubyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h4mqbubyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:ellipsis-vertical" /></template>
