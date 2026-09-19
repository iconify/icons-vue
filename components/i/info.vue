<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkd_uccph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":24};
const content = `<path class="pkd_uccph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:info" /></template>
