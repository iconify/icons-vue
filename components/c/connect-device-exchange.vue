<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rj6-sg7sb.css';
import '../../css/a/asamhsb1h.css';
import '../../css/f/fk0hwpbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rj6-sg7sb"/><path class="asamhsb1h"/><path class="fk0hwpbxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:connect-device-exchange" /></template>
