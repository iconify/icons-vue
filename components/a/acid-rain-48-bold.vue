<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh78pcczw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jh78pcczw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:acid-rain-48-bold" /></template>
