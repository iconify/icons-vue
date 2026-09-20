<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s22t9r_ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s22t9r_ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-apps-script" /></template>
