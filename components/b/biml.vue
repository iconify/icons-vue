<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfqgssbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfqgssbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:biml" /></template>
