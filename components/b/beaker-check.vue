<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okd59c11y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okd59c11y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:beaker-check" /></template>
