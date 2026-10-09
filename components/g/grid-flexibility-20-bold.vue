<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u364xbb6d.css';
import '../../css/i/ilw_03s_n.css';
import '../../css/e/e23at5bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u364xbb6d"/><path class="ilw_03s_n"/><path class="e23at5bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-flexibility-20-bold" /></template>
