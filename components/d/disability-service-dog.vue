<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hjyi-2bwz.css';
import '../../css/q/qdo1ibc6u.css';
import '../../css/a/amaijkbru.css';
import '../../css/v/voz8m8_db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hjyi-2bwz"/><path class="qdo1ibc6u"/><path class="amaijkbru"/><path class="voz8m8_db"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:disability-service-dog" /></template>
