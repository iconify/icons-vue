<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_q5fvoit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_q5fvoit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:contributor-covenant" /></template>
