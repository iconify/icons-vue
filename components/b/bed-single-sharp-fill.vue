<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcig4fbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcig4fbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-single-sharp-fill" /></template>
