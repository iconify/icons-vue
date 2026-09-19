<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5iwdvbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="m5iwdvbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:blip" /></template>
