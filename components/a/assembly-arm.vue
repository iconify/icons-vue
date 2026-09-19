<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk1mzua3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hk1mzua3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:assembly-arm" /></template>
