<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wqpfyoblb.css';
import '../../css/b/brqoombhq.css';
import '../../css/d/dzbr9ggbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wqpfyoblb"/><path class="brqoombhq"/><path class="dzbr9ggbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:inbox-check" /></template>
