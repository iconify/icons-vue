<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suo3iwr-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suo3iwr-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mail-open-x" /></template>
