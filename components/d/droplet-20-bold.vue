<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo4j70bbm.css';
import '../../css/m/mxmopzb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qo4j70bbm"/><path class="mxmopzb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:droplet-20-bold" /></template>
