<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kht38ccar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kht38ccar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:diamond-alt" /></template>
