<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuyn2ub2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuyn2ub2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google" /></template>
