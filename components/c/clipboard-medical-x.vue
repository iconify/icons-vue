<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kybmr1v5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kybmr1v5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clipboard-medical-x" /></template>
