<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s2wl61vvr.css';
import '../../css/x/x5zw6sbwv.css';
import '../../css/r/rxl27eg2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s2wl61vvr"/><path class="x5zw6sbwv"/><path class="rxl27eg2m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:cloud-gaming-service" /></template>
