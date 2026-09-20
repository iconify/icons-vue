<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gffp2tb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gffp2tb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lungs" /></template>
