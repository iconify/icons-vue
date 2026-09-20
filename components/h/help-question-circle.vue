<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/v6dkth_az.css';
import '../../css/k/kh_n3mb3b.css';
import '../../css/x/xaa72ccqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="v6dkth_az"/><path class="kh_n3mb3b"/><path class="xaa72ccqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:help-question-circle" /></template>
