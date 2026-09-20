<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pphx8ib2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pphx8ib2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codecademy" /></template>
