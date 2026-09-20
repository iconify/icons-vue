<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vap1pibst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vap1pibst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:horizontal-align-right" /></template>
