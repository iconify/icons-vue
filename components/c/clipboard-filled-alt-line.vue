<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvas_sv5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvas_sv5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clipboard-filled-alt-line" /></template>
