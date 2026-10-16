<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o84rn3bvm.css';
import '../../css/n/nbj9xhbai.css';
import '../../css/w/w742qcbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o84rn3bvm"/><path class="nbj9xhbai"/><path class="w742qcbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lidar-48" /></template>
