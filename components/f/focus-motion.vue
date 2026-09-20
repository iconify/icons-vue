<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/iecmi3svr.css';
import '../../css/n/n5amlrb_l.css';
import '../../css/v/vtz5mzbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="iecmi3svr"/><path class="n5amlrb_l"/><path class="vtz5mzbno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:focus-motion" /></template>
