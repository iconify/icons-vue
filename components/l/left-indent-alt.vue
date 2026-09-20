<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r89p1bbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r89p1bbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:left-indent-alt" /></template>
