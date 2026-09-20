<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_dz3ub_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_dz3ub_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-down-2" /></template>
