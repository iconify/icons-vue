<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q52pyccnr.css';
import '../../css/j/jmo65nxdc.css';
import '../../css/y/yyu6w0k1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q52pyccnr"/><path class="jmo65nxdc"/><path class="yyu6w0k1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-headphone-filled" /></template>
