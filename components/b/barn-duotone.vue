<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4xcodbxl.css';
import '../../css/x/xsfik-bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4xcodbxl"/><path class="xsfik-bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:barn-duotone" /></template>
