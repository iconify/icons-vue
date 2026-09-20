<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhd73iz3o.css';
import '../../css/f/fjk7q33ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fhd73iz3o"/><path class="fjk7q33ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:heyform-dark" /></template>
