<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3fak-24z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r3fak-24z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crusher-48" /></template>
