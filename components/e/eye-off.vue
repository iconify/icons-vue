<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6qob_08r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":408};
const content = `<path class="m6qob_08r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:eye-off" /></template>
