<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/z/z5jq7eatv.css';
import '../../css/j/jsl_plbqj.css';
import '../../css/b/b-4r_xb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z5jq7eatv"/><path class="jsl_plbqj"/><path class="b-4r_xb9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-view" /></template>
