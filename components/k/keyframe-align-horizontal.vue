<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxy64actr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxy64actr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:keyframe-align-horizontal" /></template>
