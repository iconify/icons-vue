<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcp77acbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcp77acbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:itunes" /></template>
