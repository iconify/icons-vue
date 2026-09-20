<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1md3142x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n1md3142x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:frown-solid" /></template>
