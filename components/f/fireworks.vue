<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wop2_bcbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wop2_bcbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:fireworks" /></template>
