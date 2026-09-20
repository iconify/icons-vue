<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek3c1gbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek3c1gbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:apple-logo" /></template>
