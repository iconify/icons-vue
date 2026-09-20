<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q55h08zgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q55h08zgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-off-sharp" /></template>
