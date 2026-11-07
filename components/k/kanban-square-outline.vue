<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_aluvvdv.css';
import '../../css/o/oj3cw1blx.css';
import '../../css/h/hepad7g3n.css';
import '../../css/w/w6r8jvb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_aluvvdv"/><path class="oj3cw1blx"/><path class="hepad7g3n"/><path clip-rule="evenodd" class="w6r8jvb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kanban-square-outline" /></template>
