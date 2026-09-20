<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqmw9v60f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqmw9v60f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:franprix" /></template>
