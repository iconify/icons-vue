<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5gc8fbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="x5gc8fbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:leaf-stroke-12" /></template>
