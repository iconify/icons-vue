<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx-_djyyn.css';
import '../../css/p/pci-8zxna.css';
import '../../css/j/j83cdtwkl.css';
import '../../css/z/z2lgmebod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lx-_djyyn"/><path class="pci-8zxna"/><path class="j83cdtwkl"/><path class="z2lgmebod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-pipeline-20-bold" /></template>
