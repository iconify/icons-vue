<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnr844bya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnr844bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:greensock" /></template>
