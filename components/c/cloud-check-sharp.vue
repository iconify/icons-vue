<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km_0wyb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km_0wyb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-check-sharp" /></template>
