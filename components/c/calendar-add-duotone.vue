<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pl91_tter.css';
import '../../css/x/x1wlzug7e.css';
import '../../css/o/oww92lb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="pl91_tter"/><path class="x1wlzug7e"/><path class="oww92lb8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:calendar-add-duotone" /></template>
