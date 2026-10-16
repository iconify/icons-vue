<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skw6qbb9b.css';
import '../../css/z/ztdjq8bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="skw6qbb9b"/><path class="ztdjq8bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:distribution-board-20-bold" /></template>
