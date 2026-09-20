<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf-x9x4-a.css';
import '../../css/j/j2fntcc6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="mf-x9x4-a"/><path class="j2fntcc6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:elevators" /></template>
