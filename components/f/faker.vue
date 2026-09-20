<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sinll_72s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sinll_72s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:faker" /></template>
