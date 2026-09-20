<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4wiwml6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="x4wiwml6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:legal-circle" /></template>
