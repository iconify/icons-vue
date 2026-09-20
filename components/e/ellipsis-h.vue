<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyw85fihm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyw85fihm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:ellipsis-h" /></template>
