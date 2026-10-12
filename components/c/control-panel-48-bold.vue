<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzpmmxj6m.css';
import '../../css/j/jrayg3xau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jzpmmxj6m"/><path class="jrayg3xau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:control-panel-48-bold" /></template>
