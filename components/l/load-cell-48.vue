<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz1cr6bmp.css';
import '../../css/t/tvqb9tb9q.css';
import '../../css/f/fm68w8yya.css';
import '../../css/f/fonho850d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pz1cr6bmp"/><path class="tvqb9tb9q"/><path class="fm68w8yya"/><path class="fonho850d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:load-cell-48" /></template>
