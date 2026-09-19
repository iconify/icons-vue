<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur-ntnenv.css';
import '../../css/k/kgjor1bvy.css';
import '../../css/h/hakimgbod.css';
import '../../css/p/p9b78ab8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ur-ntnenv"/><path class="kgjor1bvy"/><path class="hakimgbod"/><path class="p9b78ab8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:full-trash" /></template>
