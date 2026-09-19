<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb-1labtg.css';
import '../../css/f/fp79t9bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="wb-1labtg"/><path class="fp79t9bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:host-solid" /></template>
