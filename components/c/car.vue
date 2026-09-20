<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrd6dk6om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrd6dk6om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car" /></template>
