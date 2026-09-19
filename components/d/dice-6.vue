<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhcvs-bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhcvs-bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:dice-6" /></template>
