<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlenow6rc.css';
import '../../css/l/l6xz3eb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wlenow6rc"/><path class="l6xz3eb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-turbine-20" /></template>
