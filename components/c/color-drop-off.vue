<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmf64gbbe.css';
import '../../css/f/f-3byccfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pmf64gbbe"/><path class="f-3byccfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:color-drop-off" /></template>
