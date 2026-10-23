<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r24llcbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r24llcbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cable" /></template>
