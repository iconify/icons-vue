<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngwr1f4hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngwr1f4hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:black" /></template>
