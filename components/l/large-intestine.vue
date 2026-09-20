<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwa2j_kng.css';
import '../../css/c/cwd0g7-xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="pwa2j_kng"/><path class="cwd0g7-xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:large-intestine" /></template>
