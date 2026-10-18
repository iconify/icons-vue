<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoujtnlpy.css';
import '../../css/c/cso2t9k2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uoujtnlpy"/><path class="cso2t9k2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:expansion-vessel-48-bold" /></template>
