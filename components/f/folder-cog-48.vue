<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb9x9-c_l.css';
import '../../css/p/ptv8ek73j.css';
import '../../css/z/zu-oc0toa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mb9x9-c_l"/><path class="ptv8ek73j"/><path class="zu-oc0toa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-cog-48" /></template>
