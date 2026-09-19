<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6n7epy-m.css';
import '../../css/m/mexmngaav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6n7epy-m"/><path class="mexmngaav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-chevrons-right" /></template>
