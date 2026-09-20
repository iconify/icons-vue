<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf2ymx__o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uf2ymx__o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bollard" /></template>
