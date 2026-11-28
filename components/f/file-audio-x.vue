<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo90mb9-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo90mb9-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-audio-x" /></template>
