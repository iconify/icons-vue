<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa73fq75k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa73fq75k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:flip-h-alt" /></template>
