<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhi1-1nji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhi1-1nji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googlemessages" /></template>
