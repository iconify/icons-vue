<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngpo3ddrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":117,"height":116};
const content = `<path clip-rule="evenodd" class="ngpo3ddrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kibo-ui-dark" /></template>
