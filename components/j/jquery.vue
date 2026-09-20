<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oec0mgsqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oec0mgsqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:jquery" /></template>
