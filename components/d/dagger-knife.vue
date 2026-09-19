<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdp-0be3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xdp-0be3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:dagger-knife" /></template>
