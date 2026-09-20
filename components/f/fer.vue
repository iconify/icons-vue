<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvj5dzbtl.css';
import '../../css/i/inpc4rroq.css';
import '../../css/q/qapg4nbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvj5dzbtl"/><path class="inpc4rroq"/><path clip-rule="evenodd" class="qapg4nbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fer" /></template>
