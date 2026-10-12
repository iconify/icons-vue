<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zdh9olb8w.css';
import '../../css/e/ed31t1blr.css';
import '../../css/g/gm65vjmzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zdh9olb8w"/><path class="ed31t1blr"/><path class="gm65vjmzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layout-freeform-duotone" /></template>
