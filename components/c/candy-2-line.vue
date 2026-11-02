<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfiz4io-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfiz4io-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:candy-2-line" /></template>
