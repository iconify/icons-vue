<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii6g86ohh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ii6g86ohh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:heart-11" /></template>
