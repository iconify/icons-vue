<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maz01fk0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="maz01fk0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-close-fill-round" /></template>
