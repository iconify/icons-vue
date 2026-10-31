<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/m/m96f6qbnd.css';
import '../../css/i/i9fl8kbvz.css';
import '../../css/p/p41ig8b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="m96f6qbnd wm-shadow"/><path class="i9fl8kbvz wm-shadow"/><path class="p41ig8b8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:align-left" /></template>
