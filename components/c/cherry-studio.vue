<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaahlrc3c.css';
import '../../css/a/aqdf5vb7x.css';
import '../../css/d/d43wkrl0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qaahlrc3c"/><path class="aqdf5vb7x"/><path class="d43wkrl0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cherry-studio" /></template>
