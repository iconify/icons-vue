<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueqbtm0pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueqbtm0pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:drone" /></template>
