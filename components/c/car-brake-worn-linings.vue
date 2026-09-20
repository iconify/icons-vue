<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wer3vhbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wer3vhbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-brake-worn-linings" /></template>
