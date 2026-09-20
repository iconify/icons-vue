<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek2b1yb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ek2b1yb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:blazor" /></template>
