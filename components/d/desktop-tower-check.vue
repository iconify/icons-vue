<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im8sh_2qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im8sh_2qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:desktop-tower-check" /></template>
