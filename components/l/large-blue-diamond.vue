<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6gwf2-xb.css';
import '../../css/o/o_t_4_bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="z6gwf2-xb"/><path class="o_t_4_bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:large-blue-diamond" /></template>
