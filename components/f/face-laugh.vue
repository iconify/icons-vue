<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnbx4cb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnbx4cb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:face-laugh" /></template>
