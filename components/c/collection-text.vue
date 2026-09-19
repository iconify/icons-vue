<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmf28pbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="hmf28pbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-text" /></template>
