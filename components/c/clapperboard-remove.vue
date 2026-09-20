<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bld70-bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bld70-bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clapperboard-remove" /></template>
