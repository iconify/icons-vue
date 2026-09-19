<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze_c9dblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze_c9dblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:genomic" /></template>
