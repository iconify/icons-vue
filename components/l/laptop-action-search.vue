<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/u/urrt0qbsc.css';
import '../../css/c/c9qeozbdv.css';
import '../../css/a/ad3lw7vkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="urrt0qbsc"/><path class="c9qeozbdv"/><path class="ad3lw7vkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:laptop-action-search" /></template>
