<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go4i3w7cb.css';
import '../../css/e/e12zghbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go4i3w7cb"/><path class="e12zghbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ev-station" /></template>
