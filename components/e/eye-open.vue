<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/c70u1_9qk.css';
import '../../css/y/y_nsz_h-y.css';
import '../../css/g/gzhzl4bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c70u1_9qk"/><circle class="y_nsz_h-y"/><path class="gzhzl4bww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:eye-open" /></template>
