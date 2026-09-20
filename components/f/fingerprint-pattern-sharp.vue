<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qppqpm--t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qppqpm--t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fingerprint-pattern-sharp" /></template>
