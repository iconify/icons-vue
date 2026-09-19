<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pldvvq-vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pldvvq-vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:floor-lantern-group" /></template>
