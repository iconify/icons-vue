<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue3ui5iyp.css';
import '../../css/h/haz-fbj8x.css';
import '../../css/w/wryd348yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue3ui5iyp"/><path class="haz-fbj8x"/><path class="wryd348yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:diskette-bold-duotone" /></template>
