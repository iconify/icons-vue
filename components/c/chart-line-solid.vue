<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv1mxrgyg.css';
import '../../css/h/h2tie5wrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv1mxrgyg"/><path class="h2tie5wrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:chart-line-solid" /></template>
