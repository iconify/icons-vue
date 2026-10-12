<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yfp87wbpx.css';
import '../../css/f/f29fwjbso.css';
import '../../css/j/jyuddqs9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yfp87wbpx"/><path class="f29fwjbso"/><path class="jyuddqs9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:eye-duotone" /></template>
