<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp4eogk8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp4eogk8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:3dprinter-printing" /></template>
