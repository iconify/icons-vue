<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/e7ugy10kt.css';
import '../../css/g/gp72obe2t.css';
import '../../css/l/lcts5dtqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e7ugy10kt"/><path class="gp72obe2t"/><path class="lcts5dtqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:contact-round" /></template>
