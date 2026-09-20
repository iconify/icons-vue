<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3w6pbbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3w6pbbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bank-of-america" /></template>
