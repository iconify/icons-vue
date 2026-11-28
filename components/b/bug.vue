<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdvl-y1zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdvl-y1zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bug" /></template>
