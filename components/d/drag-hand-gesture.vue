<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/v7svy8bvx.css';
import '../../css/z/zilprabad.css';
import '../../css/b/b92w5yz7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v7svy8bvx"/><path class="zilprabad"/><path class="b92w5yz7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:drag-hand-gesture" /></template>
