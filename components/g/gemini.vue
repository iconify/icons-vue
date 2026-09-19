<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw_p06a2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lw_p06a2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:gemini" /></template>
