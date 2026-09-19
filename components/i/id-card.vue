<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz9-9zbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="pz9-9zbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:id-card" /></template>
