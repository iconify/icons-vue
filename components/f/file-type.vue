<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk2x82brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk2x82brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-type" /></template>
