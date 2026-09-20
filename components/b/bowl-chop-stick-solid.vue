<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-r6ewgyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e-r6ewgyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:bowl-chop-stick-solid" /></template>
