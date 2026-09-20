<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywfei79cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ywfei79cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:function-diagram-new" /></template>
