<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhu29pbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jhu29pbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:globe-alt" /></template>
