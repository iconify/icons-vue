<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg3p3ab6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lg3p3ab6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-down-stroke-12" /></template>
