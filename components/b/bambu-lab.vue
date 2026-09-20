<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e75u_thhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e75u_thhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bambu-lab" /></template>
