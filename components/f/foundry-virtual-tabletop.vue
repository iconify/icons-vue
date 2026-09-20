<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lohj11b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lohj11b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:foundry-virtual-tabletop" /></template>
