<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu09wfb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu09wfb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-edit" /></template>
