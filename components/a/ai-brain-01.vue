<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/htj3e9bhs.css';
import '../../css/t/txfxjqb6g.css';
import '../../css/i/ixt95bbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="htj3e9bhs"/><path class="txfxjqb6g"/><path class="ixt95bbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-brain-01" /></template>
