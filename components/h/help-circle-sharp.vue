<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8uhoz76d.css';
import '../../css/q/q7qow0bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h8uhoz76d"/><path class="q7qow0bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:help-circle-sharp" /></template>
