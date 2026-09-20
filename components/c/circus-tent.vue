<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vn3ohy7yk.css';
import '../../css/v/vh5twnb_y.css';
import '../../css/d/ds11oubjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vn3ohy7yk"/><path class="vh5twnb_y"/><path class="ds11oubjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:circus-tent" /></template>
