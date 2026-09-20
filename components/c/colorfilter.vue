<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hftl6jqgd.css';
import '../../css/p/pqjz-tb5y.css';
import '../../css/a/avtw3ccyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hftl6jqgd"/><path class="pqjz-tb5y"/><path class="avtw3ccyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:colorfilter" /></template>
