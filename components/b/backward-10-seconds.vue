<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/i5oofwb9h.css';
import '../../css/i/i5tsyvxih.css';
import '../../css/h/hdc8gxnie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i5oofwb9h"/><path class="i5tsyvxih"/><path class="hdc8gxnie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:backward-10-seconds" /></template>
