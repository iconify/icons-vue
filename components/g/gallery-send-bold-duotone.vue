<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwa9eupgf.css';
import '../../css/j/jut9e4-pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwa9eupgf"/><path clip-rule="evenodd" class="jut9e4-pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-send-bold-duotone" /></template>
