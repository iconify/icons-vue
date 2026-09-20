<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dij20eafv.css';
import '../../css/x/x5fi_2ghi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="ft5dv1b6b"><path class="dij20eafv"/><path class="x5fi_2ghi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:heart-alt-duotone" /></template>
