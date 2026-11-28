<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iliajm18t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iliajm18t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:align-right" /></template>
