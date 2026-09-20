<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2cwfz8jg.css';
import '../../css/s/s5kpojbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2cwfz8jg"/><path class="s5kpojbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:cpu-24" /></template>
