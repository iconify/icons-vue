<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-5yz33-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-5yz33-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:gamepad-x" /></template>
