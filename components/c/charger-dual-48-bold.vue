<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gylj85but.css';
import '../../css/d/d1rsb2bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gylj85but"/><path class="d1rsb2bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-dual-48-bold" /></template>
