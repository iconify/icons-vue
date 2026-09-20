<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e3z_iybqn.css';
import '../../css/f/fktkktbrf.css';
import '../../css/f/f8nlp98qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e3z_iybqn"/><circle class="fktkktbrf"/><path clip-rule="evenodd" class="f8nlp98qe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:image-photography" /></template>
