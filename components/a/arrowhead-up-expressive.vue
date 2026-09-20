<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scn4tpb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scn4tpb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrowhead-up-expressive" /></template>
