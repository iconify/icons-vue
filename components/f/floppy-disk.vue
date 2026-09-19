<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_0_lnbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="w_0_lnbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:floppy-disk" /></template>
