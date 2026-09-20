<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_cf4dbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_cf4dbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-photos" /></template>
