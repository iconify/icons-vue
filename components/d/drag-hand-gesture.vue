<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/j6o7377jw.css';
import '../../css/z/zilprabad.css';
import '../../css/g/gujnf0u8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j6o7377jw"/><path class="zilprabad"/><path class="gujnf0u8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:drag-hand-gesture" /></template>
