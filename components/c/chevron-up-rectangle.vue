<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ocos3pbek.css';
import '../../css/l/lxhba64ej.css';
import '../../css/p/p9tgkebiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ocos3pbek"/><path class="lxhba64ej"/><path class="p9tgkebiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-up-rectangle" /></template>
