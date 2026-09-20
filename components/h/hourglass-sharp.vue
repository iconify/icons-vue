<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7pn04bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7pn04bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hourglass-sharp" /></template>
