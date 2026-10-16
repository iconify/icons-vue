<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr4vd1rvr.css';
import '../../css/k/k16_ngbvw.css';
import '../../css/v/vlj26f7td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wr4vd1rvr"/><path class="k16_ngbvw"/><path class="vlj26f7td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-input-48" /></template>
