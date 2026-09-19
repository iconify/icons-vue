<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu73t8y-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":456,"height":512};
const content = `<path class="gu73t8y-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cake" /></template>
