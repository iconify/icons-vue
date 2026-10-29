<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh4rqfpek.css';
import '../../css/l/luoocdwcm.css';
import '../../css/m/mrtpigbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh4rqfpek"/><path class="luoocdwcm"/><path class="mrtpigbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:align-center" /></template>
