<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfr-b9b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfr-b9b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:adp" /></template>
