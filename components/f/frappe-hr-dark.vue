<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk4vp-xsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rk4vp-xsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-hr-dark" /></template>
