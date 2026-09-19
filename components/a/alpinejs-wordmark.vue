<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tblo-pfoi.css';
import '../../css/s/s26yw0bri.css';
import '../../css/m/mdbg4dcqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tblo-pfoi"/><path clip-rule="evenodd" class="s26yw0bri"/><path clip-rule="evenodd" class="mdbg4dcqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:alpinejs-wordmark" /></template>
