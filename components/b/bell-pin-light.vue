<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t8pej6b5h.css';
import '../../css/h/hzsbvcczg.css';
import '../../css/l/le0nq6m2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="t8pej6b5h"/><path class="hzsbvcczg"/><circle class="le0nq6m2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:bell-pin-light" /></template>
