<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nvc1yyymo.css';
import '../../css/c/c6lh6cqlm.css';
import '../../css/d/da1rzrbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nvc1yyymo"/><path class="c6lh6cqlm"/><path class="da1rzrbyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gallery-vertical-duotone" /></template>
