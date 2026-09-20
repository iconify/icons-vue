<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inyb3balg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inyb3balg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bin-sharp-fill" /></template>
