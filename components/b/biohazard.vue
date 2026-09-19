<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg_wpcd8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":962};
const content = `<path class="kg_wpcd8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:biohazard" /></template>
