<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owwit_mkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="owwit_mkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:diagram-successor" /></template>
