<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stss5vbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":491,"height":512};
const content = `<path class="stss5vbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:awk" /></template>
