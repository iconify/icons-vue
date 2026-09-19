<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tquyp2c9p.css';
import '../../css/f/fd9f55byh.css';
import '../../css/c/cui1j9-yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tquyp2c9p"/><path class="fd9f55byh"/><path class="cui1j9-yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:cast" /></template>
