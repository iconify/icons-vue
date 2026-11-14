<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/z/zt1kts5cj.css';
import '../../css/x/x07gi_bsw.css';
import '../../css/o/osr3gdbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zt1kts5cj"/><path class="x07gi_bsw"/><path class="osr3gdbap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:analytics-down" /></template>
