<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz8d8p7vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz8d8p7vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:juniper-networks" /></template>
