<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/e/emrjjuzor.css';
import '../../css/b/bcrcl3pcu.css';
import '../../css/o/oiemdrb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="emrjjuzor"/><path class="bcrcl3pcu"/><path class="oiemdrb8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:globe-light" /></template>
