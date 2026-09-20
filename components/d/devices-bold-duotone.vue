<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i4xinab9i.css';
import '../../css/p/pq64lglul.css';
import '../../css/v/vfmtqtm3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i4xinab9i"/><path class="pq64lglul"/><path class="vfmtqtm3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:devices-bold-duotone" /></template>
