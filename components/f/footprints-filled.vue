<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq12sv_du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq12sv_du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:footprints-filled" /></template>
