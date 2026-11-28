<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3rr2lbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3rr2lbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:anchor" /></template>
