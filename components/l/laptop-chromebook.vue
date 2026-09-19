<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzxrjhs0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="mzxrjhs0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:laptop-chromebook" /></template>
