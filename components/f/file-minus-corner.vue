<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1em_ve-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1em_ve-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-minus-corner" /></template>
