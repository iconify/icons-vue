<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/u/uumdjbb7e.css';
import '../../css/g/gph90cbak.css';
import '../../css/o/ojg46yc6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="uumdjbb7e"/><path class="gph90cbak"/><path class="ojg46yc6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:ai-generate-voice-spark-2-flat" /></template>
