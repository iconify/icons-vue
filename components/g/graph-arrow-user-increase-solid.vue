<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paj-fcc1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="paj-fcc1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:graph-arrow-user-increase-solid" /></template>
