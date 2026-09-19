<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcny89buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":586,"height":1000};
const content = `<path class="dcny89buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:location" /></template>
