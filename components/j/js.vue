<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w49j0rbvv.css';
import '../../css/q/q84ioub0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="bi12bsetm"><path class="w49j0rbvv"/><path class="q84ioub0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:js" /></template>
