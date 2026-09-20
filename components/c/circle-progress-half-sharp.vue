<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_6n9bb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_6n9bb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-progress-half-sharp" /></template>
