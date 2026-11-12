<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frl9spbxs.css';
import '../../css/b/bocz3tbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="frl9spbxs"/><path class="bocz3tbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fhem-light" /></template>
