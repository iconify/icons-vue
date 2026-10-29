<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n4ra6qb5a.css';
import '../../css/h/h4uzyibtm.css';
import '../../css/a/a5neubxnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="n4ra6qb5a"/><path class="h4uzyibtm wm-a"/><path class="a5neubxnb wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flashlight" /></template>
