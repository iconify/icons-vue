<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gid1uccfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gid1uccfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:grab" /></template>
