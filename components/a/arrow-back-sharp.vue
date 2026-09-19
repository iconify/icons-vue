<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfvo-obul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gfvo-obul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-back-sharp" /></template>
