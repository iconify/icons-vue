<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia0lysvrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ia0lysvrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:component-pascal" /></template>
