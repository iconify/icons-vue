<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdltqurcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gdltqurcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:end-point-branches-flat" /></template>
