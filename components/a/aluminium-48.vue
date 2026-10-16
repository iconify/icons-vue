<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa8mtjico.css';
import '../../css/x/xs22834vg.css';
import '../../css/v/v4yfn2nbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pa8mtjico"/><path class="xs22834vg"/><path class="v4yfn2nbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:aluminium-48" /></template>
