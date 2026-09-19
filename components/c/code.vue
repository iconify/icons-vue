<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj10jwbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj10jwbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:code" /></template>
