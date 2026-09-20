<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g43-tlbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g43-tlbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ethers" /></template>
