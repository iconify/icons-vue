<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj00pl8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nrj00pl8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:add-shield-half" /></template>
