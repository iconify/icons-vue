<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyxrw189h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyxrw189h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:exoscale" /></template>
