<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe7iz5bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe7iz5bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:branch" /></template>
