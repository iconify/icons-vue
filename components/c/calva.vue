<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azipg_esx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="azipg_esx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:calva" /></template>
