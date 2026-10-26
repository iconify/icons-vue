<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzap8g49r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zzap8g49r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:balloons" /></template>
