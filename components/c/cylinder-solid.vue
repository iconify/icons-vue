<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3aexnb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3aexnb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cylinder-solid" /></template>
