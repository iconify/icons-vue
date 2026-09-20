<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clawo4fnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="clawo4fnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:geo-active" /></template>
