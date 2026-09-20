<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/w/wo9nqsi3z.css';
import '../../css/e/e7l1odb0b.css';
import '../../css/f/f6jbyibzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wo9nqsi3z"/><ellipse class="e7l1odb0b"/><path class="f6jbyibzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:ice-hockey" /></template>
