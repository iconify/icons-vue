<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1ul3kb-l.css';
import '../../css/m/meqydp0-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c1ul3kb-l"/><path class="meqydp0-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:iris-scan-target" /></template>
