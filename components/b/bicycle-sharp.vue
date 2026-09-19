<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duy4fwuoh.css';
import '../../css/y/ym7s1o7nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="duy4fwuoh"/><path class="ym7s1o7nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bicycle-sharp" /></template>
