<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz6mhscer.css';
import '../../css/i/i7nmstb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mz6mhscer ouiIcon__fillSecondary"/><path class="i7nmstb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-canvas" /></template>
