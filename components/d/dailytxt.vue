<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewinqubjx.css';
import '../../css/j/js6qhmbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ewinqubjx"/><path class="js6qhmbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dailytxt" /></template>
