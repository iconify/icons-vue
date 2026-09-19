<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm2zggi6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="dm2zggi6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:jedi" /></template>
