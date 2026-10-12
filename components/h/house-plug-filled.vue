<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g67_cgb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g67_cgb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:house-plug-filled" /></template>
