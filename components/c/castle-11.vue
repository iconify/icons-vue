<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn3et2b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="yn3et2b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:castle-11" /></template>
