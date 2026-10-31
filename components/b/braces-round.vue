<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga4spfbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga4spfbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:braces-round" /></template>
