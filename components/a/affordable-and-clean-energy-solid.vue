<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lombof_ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lombof_ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:affordable-and-clean-energy-solid" /></template>
