<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2mbsmb2r.css';
import '../../css/x/xyie74fxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2mbsmb2r"/><path class="xyie74fxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:init-container-outlined" /></template>
