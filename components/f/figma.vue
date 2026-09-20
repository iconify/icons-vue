<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/v9d36vgse.css';
import '../../css/o/oxkfxll7r.css';
import '../../css/q/qozean2np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v9d36vgse"/><path class="oxkfxll7r"/><path class="qozean2np"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:figma" /></template>
