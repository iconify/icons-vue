<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyt806nrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyt806nrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cncf" /></template>
