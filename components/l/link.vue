<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4wkg5yij.css';
import '../../css/n/nv5c7mbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4wkg5yij"/><path class="nv5c7mbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:link" /></template>
