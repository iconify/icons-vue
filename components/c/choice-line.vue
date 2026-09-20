<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scf9pfbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scf9pfbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:choice-line" /></template>
