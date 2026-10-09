<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m62_8ratf.css';
import '../../css/l/lrevnvbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m62_8ratf"/><path class="lrevnvbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-module-20" /></template>
