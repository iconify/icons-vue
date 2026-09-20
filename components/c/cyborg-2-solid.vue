<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rns7-ac9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rns7-ac9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cyborg-2-solid" /></template>
