<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwymv390r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwymv390r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:list-ui-alt" /></template>
