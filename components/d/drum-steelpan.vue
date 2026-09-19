<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi0991b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="qi0991b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:drum-steelpan" /></template>
