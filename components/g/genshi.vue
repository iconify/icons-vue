<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzv_ynb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":310,"height":512};
const content = `<path class="tzv_ynb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:genshi" /></template>
