<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-zvc55rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-zvc55rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:align-left-2-solid" /></template>
