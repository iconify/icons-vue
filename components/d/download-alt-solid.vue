<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra69dbbfc.css';
import '../../css/u/u0vmqablo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra69dbbfc"/><path class="u0vmqablo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:download-alt-solid" /></template>
