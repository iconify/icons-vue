<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhycuvbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="vhycuvbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hexagon-nodes-bolt" /></template>
