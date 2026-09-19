<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhqq6-j_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uhqq6-j_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:assembly-motorola" /></template>
