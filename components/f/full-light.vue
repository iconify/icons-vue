<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpk_m-oiv.css';
import '../../css/q/qhbzephbs.css';
import '../../css/y/ydp0b-b3w.css';
import '../../css/c/cu0gh7bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpk_m-oiv"/><path class="qhbzephbs"/><path class="ydp0b-b3w"/><path class="cu0gh7bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:full-light" /></template>
