<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr_ri1bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rr_ri1bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:genie-lamp-with-stardust" /></template>
