<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcdt_kyqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcdt_kyqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:hunyuan" /></template>
