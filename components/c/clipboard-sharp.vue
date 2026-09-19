<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiv1pnq9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uiv1pnq9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:clipboard-sharp" /></template>
