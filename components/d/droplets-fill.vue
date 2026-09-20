<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqw673b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqw673b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:droplets-fill" /></template>
