<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0_uobbtg.css';
import '../../css/u/ussqqxbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="r0_uobbtg"/><path class="ussqqxbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:hotel" /></template>
