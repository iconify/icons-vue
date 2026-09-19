<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsvm4h_mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jsvm4h_mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-pumpkin" /></template>
