<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdzkjibvl.css';
import '../../css/e/e4qlnbc0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdzkjibvl"/><path clip-rule="evenodd" class="e4qlnbc0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-square-bold" /></template>
