<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smq2_2b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="smq2_2b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:generic-sorting-desc" /></template>
