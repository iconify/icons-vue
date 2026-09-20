<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2rwiks3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m2rwiks3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:interpreter" /></template>
