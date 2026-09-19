<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxfyjvden.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="vxfyjvden"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:archway" /></template>
