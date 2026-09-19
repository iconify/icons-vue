<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksiwmgbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":833};
const content = `<path class="ksiwmgbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flowup" /></template>
