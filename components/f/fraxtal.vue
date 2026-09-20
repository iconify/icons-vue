<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smr47_3mh.css';
import '../../css/p/ph-spx85e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smr47_3mh"/><path class="ph-spx85e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fraxtal" /></template>
