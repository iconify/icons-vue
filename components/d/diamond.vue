<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk6phkbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk6phkbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:diamond" /></template>
