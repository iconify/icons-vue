<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxvf2ubem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vxvf2ubem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:collapse-right" /></template>
