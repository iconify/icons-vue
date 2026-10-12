<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bprebx11j.css';
import '../../css/o/ofznhc5pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bprebx11j"/><path class="ofznhc5pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:control-panel-20-bold" /></template>
