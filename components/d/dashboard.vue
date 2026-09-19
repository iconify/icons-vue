<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw2mo3r6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":700,"height":700};
const content = `<path class="gw2mo3r6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:dashboard" /></template>
