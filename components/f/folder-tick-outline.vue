<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3ke_fu8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m3ke_fu8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:folder-tick-outline" /></template>
