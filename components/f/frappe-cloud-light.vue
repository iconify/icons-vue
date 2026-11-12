<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk0l0vvyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tk0l0vvyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-cloud-light" /></template>
