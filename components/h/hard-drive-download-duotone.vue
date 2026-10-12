<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aly3ipb5i.css';
import '../../css/o/oly-m626v.css';
import '../../css/q/qt56rzevo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="aly3ipb5i"/><path class="oly-m626v"/><path class="qt56rzevo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hard-drive-download-duotone" /></template>
