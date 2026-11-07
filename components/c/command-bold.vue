<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot-rahdwk.css';
import '../../css/m/mk7apdhpz.css';
import '../../css/f/fgrlfobbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot-rahdwk"/><path class="mk7apdhpz"/><path class="fgrlfobbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:command-bold" /></template>
