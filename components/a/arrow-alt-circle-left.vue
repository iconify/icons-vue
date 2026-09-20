<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rslkvhswy.css';
import '../../css/u/ug_dfdboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rslkvhswy"/><path class="ug_dfdboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-alt-circle-left" /></template>
