<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxfzo_blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxfzo_blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:case-lower-solid" /></template>
