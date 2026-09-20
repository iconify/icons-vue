<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxd2nobky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxd2nobky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevron-left-sharp-fill" /></template>
