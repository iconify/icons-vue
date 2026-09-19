<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/s/s3nyltbvc.css';
import '../../css/p/pi0z5lblf.css';
import '../../css/c/cgmlxbbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s3nyltbvc"/><path class="pi0z5lblf"/><path class="cgmlxbbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:library" /></template>
