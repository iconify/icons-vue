<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovp4tye2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovp4tye2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:diagram-dash-circle-large-head" /></template>
