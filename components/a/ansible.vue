<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djw3wseim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djw3wseim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ansible" /></template>
