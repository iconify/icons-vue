<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u95e4sw8e.css';
import '../../css/l/lfn44k03n.css';
import '../../css/i/i_mq2ccik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u95e4sw8e"/><path class="lfn44k03n"/><path class="i_mq2ccik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clipboard-plus-48-bold" /></template>
