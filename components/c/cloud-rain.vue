<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uklv7lbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uklv7lbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cloud-rain" /></template>
