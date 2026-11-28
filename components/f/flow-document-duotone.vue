<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_8em22pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary s_8em22pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-document-duotone" /></template>
