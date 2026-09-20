<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsjj6nxig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsjj6nxig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:calculator-alt" /></template>
