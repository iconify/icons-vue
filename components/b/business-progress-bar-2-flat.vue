<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/f6zu09hhk.css';
import '../../css/a/afl5k8dzu.css';
import '../../css/n/na4f4--6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="f6zu09hhk"/><path class="afl5k8dzu"/><path class="na4f4--6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:business-progress-bar-2-flat" /></template>
